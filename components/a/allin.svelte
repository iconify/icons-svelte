<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvzfdpbjs.css';
import '../../css/g/gicv_hb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xvzfdpbjs"/><path class="gicv_hb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:allin" {...props}></Icon>
