<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fodq4_j6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="fodq4_j6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:ebay" {...props}></Icon>
