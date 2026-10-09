<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8rpcmbtb.css';
import '../../css/q/qeaq1eplb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i8rpcmbtb"/><path class="qeaq1eplb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuse-20" {...props}></Icon>
