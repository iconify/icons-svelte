<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxg8f6bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="cxg8f6bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:eraser-stroke-12" {...props}></Icon>
