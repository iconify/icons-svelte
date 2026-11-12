<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rku15hbsi.css';
import '../../css/p/pp9v2l8_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rku15hbsi"/><path class="pp9v2l8_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flow-like" {...props}></Icon>
