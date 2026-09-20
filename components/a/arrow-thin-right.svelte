<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/navdlkbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="navdlkbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:arrow-thin-right" {...props}></Icon>
