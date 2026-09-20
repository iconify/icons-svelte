<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhbyxpbbq.css';
import '../../css/p/pk02s0tyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zhbyxpbbq"/><path class="pk02s0tyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:erugo-light" {...props}></Icon>
