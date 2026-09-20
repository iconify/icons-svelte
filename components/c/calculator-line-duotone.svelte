<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rnt97vblj.css';
import '../../css/s/sttdwq4fh.css';
import '../../css/e/ee7yz0sic.css';
import '../../css/w/wkk2wqcxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rnt97vblj"/><path class="sttdwq4fh"/><path class="ee7yz0sic"/><path class="wkk2wqcxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:calculator-line-duotone" {...props}></Icon>
