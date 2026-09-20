<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/h_mn9ybmc.css';
import '../../css/a/a4-4zob5u.css';
import '../../css/i/icnalvben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="h_mn9ybmc"/><path class="a4-4zob5u"/><path class="icnalvben"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:camera" {...props}></Icon>
