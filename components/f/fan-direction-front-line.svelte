<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haqr67bmp.css';
import '../../css/e/e2-vdac3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haqr67bmp"/><path class="e2-vdac3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fan-direction-front-line" {...props}></Icon>
