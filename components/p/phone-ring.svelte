<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyw6vlvsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyw6vlvsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-ring" {...props}></Icon>
