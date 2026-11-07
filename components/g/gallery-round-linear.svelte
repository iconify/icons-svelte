<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xvjk-cbox.css';
import '../../css/d/de9gu_b1y.css';
import '../../css/k/kg-2ylb5o.css';
import '../../css/e/eqv3evbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><circle class="de9gu_b1y"/><path class="kg-2ylb5o"/><path class="eqv3evbyx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-round-linear" {...props}></Icon>
