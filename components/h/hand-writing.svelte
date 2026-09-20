<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsnaprmvy.css';
import '../../css/k/kqrt5ob_v.css';
import '../../css/s/s6m-bfbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bsnaprmvy"/><path class="kqrt5ob_v"/><path class="s6m-bfbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:hand-writing" {...props}></Icon>
