<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p1ikf6bxi.css';
import '../../css/p/piiefhb4u.css';
import '../../css/t/t94b19a8b.css';
import '../../css/u/uecn3vbjn.css';
import '../../css/q/qp33kjbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":151};
const content = `<g class="ft5dv1b6b"><path class="p1ikf6bxi"/><path class="piiefhb4u"/><path class="t94b19a8b"/><path class="uecn3vbjn"/><path class="qp33kjbei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:my" {...props}></Icon>
