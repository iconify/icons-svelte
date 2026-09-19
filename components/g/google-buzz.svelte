<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjeo1t3ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":464};
const content = `<path class="jjeo1t3ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:google-buzz" {...props}></Icon>
