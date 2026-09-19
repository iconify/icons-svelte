<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t8hauoi6q.css';
import '../../css/i/i5_8b_byv.css';
import '../../css/p/pu0hdob-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t8hauoi6q"/><path class="i5_8b_byv"/><path class="pu0hdob-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mask" {...props}></Icon>
