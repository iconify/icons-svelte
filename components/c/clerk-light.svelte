<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qgykhgyqv.css';
import '../../css/t/txb2yy2ma.css';
import '../../css/e/ebco1zmpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="ft5dv1b6b"><circle class="qgykhgyqv"/><path class="txb2yy2ma"/><path class="ebco1zmpc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:clerk-light" {...props}></Icon>
