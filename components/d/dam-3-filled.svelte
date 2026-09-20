<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxnxkm_gj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxnxkm_gj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dam-3-filled" {...props}></Icon>
