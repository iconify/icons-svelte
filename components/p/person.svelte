<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bl_l48dcr.css';
import '../../css/v/vrio1vbcf.css';
import '../../css/k/kdgt5ac4e.css';
import '../../css/a/ak0v_fljm.css';
import '../../css/q/q-0tevbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" class="bl_l48dcr"><path class="vrio1vbcf"/><path class="kdgt5ac4e"/></g><circle class="ak0v_fljm"/><path class="q-0tevbrd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:person" {...props}></Icon>
