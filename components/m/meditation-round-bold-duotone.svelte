<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfx_j7n7f.css';
import '../../css/w/wh26rrx6c.css';
import '../../css/c/cs_t9bc7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfx_j7n7f"/><path clip-rule="evenodd" class="wh26rrx6c"/><path class="cs_t9bc7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:meditation-round-bold-duotone" {...props}></Icon>
