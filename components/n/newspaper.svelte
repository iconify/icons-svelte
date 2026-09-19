<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjchplbvr.css';
import '../../css/c/cbd476sji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zjchplbvr"/><path class="cbd476sji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:newspaper" {...props}></Icon>
