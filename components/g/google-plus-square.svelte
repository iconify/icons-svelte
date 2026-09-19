<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-uyfqi-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="a-uyfqi-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:google-plus-square" {...props}></Icon>
