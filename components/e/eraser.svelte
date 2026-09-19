<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfwm_-4ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sfwm_-4ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:eraser" {...props}></Icon>
