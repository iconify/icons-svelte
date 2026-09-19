<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1w7dacyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="r1w7dacyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:google-plus-square" {...props}></Icon>
