<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3tb4dbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a3tb4dbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:die-face-with-four-pips" {...props}></Icon>
