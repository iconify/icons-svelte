<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib5j_-bhr.css';
import '../../css/t/t5_nw5bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ib5j_-bhr"/><path class="t5_nw5bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:chart-line" {...props}></Icon>
