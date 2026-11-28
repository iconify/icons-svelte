<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehl-jxdfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehl-jxdfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:camera-lock" {...props}></Icon>
