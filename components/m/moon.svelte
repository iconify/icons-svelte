<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg-zy6fwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg-zy6fwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:moon" {...props}></Icon>
