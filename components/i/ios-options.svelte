<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts2-1lbsz.css';
import '../../css/n/nv41fibrk.css';
import '../../css/q/qz6wmnbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ts2-1lbsz"/><path class="nv41fibrk"/><path class="qz6wmnbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-options" {...props}></Icon>
