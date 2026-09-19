<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xrl_5-b0c.css';
import '../../css/b/b_10b0_-a.css';
import '../../css/q/qn8_xfbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xrl_5-b0c"/><path class="b_10b0_-a"/><path class="qn8_xfbjc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pan-02" {...props}></Icon>
