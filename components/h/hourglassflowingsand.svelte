<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df57ckmtv.css';
import '../../css/d/df24pzbxt.css';
import '../../css/c/co_gutb3f.css';
import '../../css/m/mamssyaqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="df57ckmtv"/><path class="df24pzbxt"/><path class="co_gutb3f"/><path class="mamssyaqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:hourglassflowingsand" {...props}></Icon>
