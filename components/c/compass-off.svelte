<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmo45ubml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmo45ubml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:compass-off" {...props}></Icon>
