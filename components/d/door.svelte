<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/kinyqzbsz.css';
import '../../css/s/szjd6r78e.css';
import '../../css/p/p103cbcyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(4 3)" class="bi12bsetm"><path class="kinyqzbsz"/><path class="szjd6r78e"/><circle class="p103cbcyv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:door" {...props}></Icon>
