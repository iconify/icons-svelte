<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mq_nynmza.css';
import '../../css/q/q_udj0h0z.css';
import '../../css/x/x6w93yb_v.css';
import '../../css/v/vr_ysibut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mq_nynmza"/><path class="q_udj0h0z"/><path class="x6w93yb_v"/><path class="vr_ysibut"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hurricane-outline" {...props}></Icon>
