<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmcj6_b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xmcj6_b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:filter" {...props}></Icon>
