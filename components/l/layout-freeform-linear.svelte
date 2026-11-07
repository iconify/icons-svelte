<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f8rmb_b-y.css';
import '../../css/e/et_co0qle.css';
import '../../css/o/oxww_b3zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f8rmb_b-y"/><path class="et_co0qle"/><path class="oxww_b3zx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:layout-freeform-linear" {...props}></Icon>
