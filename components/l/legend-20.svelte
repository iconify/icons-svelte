<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkx3xqbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nkx3xqbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:legend-20" {...props}></Icon>
