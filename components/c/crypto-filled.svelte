<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1zn45bnx.css';
import '../../css/l/lx2u58bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1zn45bnx"/><path class="lx2u58bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:crypto-filled" {...props}></Icon>
