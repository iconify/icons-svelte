<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz941qnwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sz941qnwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:codepen" {...props}></Icon>
