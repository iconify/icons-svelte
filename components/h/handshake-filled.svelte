<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxjj8npel.css';
import '../../css/l/l2afcqtvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxjj8npel"/><path class="l2afcqtvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:handshake-filled" {...props}></Icon>
