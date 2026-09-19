<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz8ivg24j.css';
import '../../css/f/fj_4_cb3o.css';
import '../../css/i/ib_iefblh.css';
import '../../css/m/msikxacrd.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 qz8ivg24j"/><path class="clr-i-outline clr-i-outline-path-2 fj_4_cb3o"/><path class="clr-i-outline clr-i-outline-path-3 ib_iefblh"/><path class="clr-i-outline clr-i-outline-path-4 msikxacrd"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:camera-line" {...props}></Icon>
