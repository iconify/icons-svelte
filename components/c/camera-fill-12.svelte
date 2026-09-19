<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z48-j6bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z48-j6bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:camera-fill-12" {...props}></Icon>
