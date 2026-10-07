<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tfls_ccga.css';
import '../../css/x/x6y2ap1ue.css';
import '../../css/b/b6u2wybtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tfls_ccga"/><path class="x6y2ap1ue"/><path class="b6u2wybtn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:group" {...props}></Icon>
