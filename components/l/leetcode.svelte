<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq0yy1vxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vq0yy1vxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:leetcode" {...props}></Icon>
