<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upjig_pzx.css';
import '../../css/m/mii1e_b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upjig_pzx"/><path clip-rule="evenodd" class="mii1e_b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:iou-filled" {...props}></Icon>
