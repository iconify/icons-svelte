<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t7n_a516v.css';
import '../../css/r/rwyyhnb2f.css';
import '../../css/q/qgl0b2pvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t7n_a516v"/><path class="rwyyhnb2f"/><path class="qgl0b2pvl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-shake-linear" {...props}></Icon>
