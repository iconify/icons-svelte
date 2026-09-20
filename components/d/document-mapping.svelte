<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es7dcmbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="es7dcmbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:document-mapping" {...props}></Icon>
