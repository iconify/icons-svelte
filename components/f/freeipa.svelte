<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3zbv3b1e.css';
import '../../css/z/zu9lzmbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v3zbv3b1e"/><path class="zu9lzmbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freeipa" {...props}></Icon>
