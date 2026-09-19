<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s31t99skb.css';
import '../../css/u/uii4avzkv.css';
import '../../css/d/d2mvnsbwq.css';
import '../../css/a/ah0waennr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="s31t99skb"/><circle class="uii4avzkv"/><path class="d2mvnsbwq"/><path class="ah0waennr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-cart-add" {...props}></Icon>
