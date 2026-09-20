<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-6_194sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m-6_194sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:angelfish-under-water" {...props}></Icon>
