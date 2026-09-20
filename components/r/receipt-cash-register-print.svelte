<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s--n7r_0v.css';
import '../../css/f/fes63hbvs.css';
import '../../css/n/nczupsdbg.css';
import '../../css/n/n5lgf897j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="s--n7r_0v"/><path class="fes63hbvs"/><path class="nczupsdbg"/><path class="n5lgf897j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:receipt-cash-register-print" {...props}></Icon>
