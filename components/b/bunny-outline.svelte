<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywii24byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywii24byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bunny-outline" {...props}></Icon>
