<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjr-_su-k.css';
import '../../css/l/l_cw2_bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xjr-_su-k"/><path class="l_cw2_bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:message-queue" {...props}></Icon>
