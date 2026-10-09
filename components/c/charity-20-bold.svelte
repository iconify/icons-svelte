<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur5l4w8hg.css';
import '../../css/n/nqiq-nbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ur5l4w8hg"/><path class="nqiq-nbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charity-20-bold" {...props}></Icon>
