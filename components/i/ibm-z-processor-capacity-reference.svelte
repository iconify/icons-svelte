<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8dna0b9r.css';
import '../../css/h/hgwl5bclr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l8dna0b9r"/><path class="hgwl5bclr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-z-processor-capacity-reference" {...props}></Icon>
