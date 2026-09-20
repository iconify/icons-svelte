<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ph0ccpa.css';
import '../../css/u/uxitrobbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ph0ccpa"/><path class="uxitrobbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:delivery-truck-fill" {...props}></Icon>
