<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/aymhwhb8v.css';
import '../../css/e/er5hmdbdf.css';
import '../../css/d/deivui2dq.css';
import '../../css/x/xhkm7y-hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aymhwhb8v"/><path class="er5hmdbdf"/><path class="deivui2dq"/><path class="xhkm7y-hu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:calculator-linear" {...props}></Icon>
