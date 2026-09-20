<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/v9bnnp-6c.css';
import '../../css/g/gcfr_k89q.css';
import '../../css/j/j_l5n-1bx.css';
import '../../css/o/oi8yi9bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v9bnnp-6c"/><circle class="gcfr_k89q"/><circle class="j_l5n-1bx"/><path class="oi8yi9bsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:hockey-mask" {...props}></Icon>
