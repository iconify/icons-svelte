<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/k/kv98g033q.css';
import '../../css/t/thed6-b2p.css';
import '../../css/f/f4vx4ccga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kv98g033q"/><path class="thed6-b2p"/><path class="f4vx4ccga"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:headset-off-sharp-duotone" {...props}></Icon>
