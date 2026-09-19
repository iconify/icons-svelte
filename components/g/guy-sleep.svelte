<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv_xycegq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mv_xycegq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:guy-sleep" {...props}></Icon>
