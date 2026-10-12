<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vu33wubzx.css';
import '../../css/e/ezpok6d0o.css';
import '../../css/d/drn3qgbsh.css';
import '../../css/q/q668hw6hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vu33wubzx"/><path class="ezpok6d0o"/><path class="drn3qgbsh"/><path class="q668hw6hc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:playing-cards-fan-duotone" {...props}></Icon>
