<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4gcyob3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="k4gcyob3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:caret-square-right" {...props}></Icon>
