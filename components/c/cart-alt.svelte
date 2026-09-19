<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duhrwdb0w.css';
import '../../css/s/s31t99skb.css';
import '../../css/p/pvk172brt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duhrwdb0w"/><circle class="s31t99skb"/><circle class="pvk172brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:cart-alt" {...props}></Icon>
