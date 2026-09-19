<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cezurnb4k.css';
import '../../css/e/e25gc_mcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cezurnb4k"/><path class="e25gc_mcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:calculator-check" {...props}></Icon>
