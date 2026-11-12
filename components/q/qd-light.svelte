<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxz6df3mx.css';
import '../../css/d/dg0y8obci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bxz6df3mx"/><path class="dg0y8obci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qd-light" {...props}></Icon>
