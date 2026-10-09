<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxtlryb9c.css';
import '../../css/c/cc-mqixje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rxtlryb9c"/><path class="cc-mqixje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-tub-20-bold" {...props}></Icon>
