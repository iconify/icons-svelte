<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdu2pbcie.css';
import '../../css/z/z8gtf7k7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kdu2pbcie"/><path class="z8gtf7k7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-horizontal" {...props}></Icon>
