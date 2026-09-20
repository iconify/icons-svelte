<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7039bbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x7039bbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:calm-face" {...props}></Icon>
