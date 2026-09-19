<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s31t99skb.css';
import '../../css/u/uii4avzkv.css';
import '../../css/d/drt_omb2n.css';
import '../../css/v/vi7rz9k8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="s31t99skb"/><circle class="uii4avzkv"/><path class="drt_omb2n"/><path class="vi7rz9k8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:cart-download" {...props}></Icon>
