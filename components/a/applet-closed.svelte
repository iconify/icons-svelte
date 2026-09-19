<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq7uf_biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xq7uf_biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:applet-closed" {...props}></Icon>
