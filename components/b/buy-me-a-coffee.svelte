<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t39s4jb2d.css';
import '../../css/k/kvhhhz9be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t39s4jb2d"/><path class="kvhhhz9be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:buy-me-a-coffee" {...props}></Icon>
