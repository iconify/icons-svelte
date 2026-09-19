<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/mia96ztce.css';
import '../../css/e/e5igkrbgq.css';
import '../../css/r/rum7tqgct.css';
import '../../css/c/cvn0a4b9a.css';
import '../../css/k/k-fhzb54s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="mia96ztce"/><path class="e5igkrbgq"/><path class="rum7tqgct"/><path class="cvn0a4b9a"/><path class="k-fhzb54s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:move-y" {...props}></Icon>
