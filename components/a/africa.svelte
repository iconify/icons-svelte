<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx07y-bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hx07y-bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:africa" {...props}></Icon>
