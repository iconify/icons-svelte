<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coivkzecr.css';
import '../../css/i/i0zpy4bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="coivkzecr"/><path class="i0zpy4bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-heart-20-bold" {...props}></Icon>
