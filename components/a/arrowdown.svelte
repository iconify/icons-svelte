<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtkdf2igp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gtkdf2igp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:arrowdown" {...props}></Icon>
