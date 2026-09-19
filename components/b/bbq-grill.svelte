<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pdwrcuibi.css';
import '../../css/r/rpt9-pb5g.css';
import '../../css/c/c7nozwbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pdwrcuibi"/><path class="rpt9-pb5g"/><path class="c7nozwbju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bbq-grill" {...props}></Icon>
