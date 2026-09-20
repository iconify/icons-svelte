<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_xc13bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="k_xc13bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:grocery-11" {...props}></Icon>
