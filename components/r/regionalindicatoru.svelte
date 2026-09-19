<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxcivhq7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pxcivhq7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:regionalindicatoru" {...props}></Icon>
