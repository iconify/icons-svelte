<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwss-ebkl.css';
import '../../css/b/bd5wmoffp.css';
import '../../css/q/qdq3nabuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rwss-ebkl"/><path class="bd5wmoffp"/><path class="qdq3nabuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:collision" {...props}></Icon>
