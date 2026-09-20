<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynvcx2b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1549,"height":1881};
const content = `<path class="ynvcx2b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:avanza" {...props}></Icon>
