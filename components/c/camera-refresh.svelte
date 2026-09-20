<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqk-0y0et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqk-0y0et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-refresh" {...props}></Icon>
