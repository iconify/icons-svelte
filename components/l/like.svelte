<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wss56ybga.css';
import '../../css/p/p3ixe5bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="wss56ybga"/><path class="p3ixe5bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:like" {...props}></Icon>
