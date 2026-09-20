<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sfdv74bik.css';
import '../../css/m/medbz2b1j.css';
import '../../css/r/rfgv0sb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="rotate(-90 10.5 8.5)" class="bi12bsetm"><path class="sfdv74bik"/><path class="medbz2b1j"/><circle class="rfgv0sb9j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:printer" {...props}></Icon>
