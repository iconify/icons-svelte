<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckjs4eb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ckjs4eb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:africarxiv-square" {...props}></Icon>
