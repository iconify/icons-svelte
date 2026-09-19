<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv_l09bks.css';
import '../../css/k/kv-q3cc2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vv_l09bks"/><path class="kv-q3cc2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:low-vision" {...props}></Icon>
