<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glhr003fr.css';
import '../../css/s/s31t99skb.css';
import '../../css/u/uii4avzkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glhr003fr"/><circle class="s31t99skb"/><circle class="uii4avzkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:cart" {...props}></Icon>
