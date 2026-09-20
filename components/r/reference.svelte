<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/pfxmy0brn.css';
import '../../css/m/mro1p6pmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="n1lsf0bnc"><path class="pfxmy0brn"/><path class="mro1p6pmy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:reference" {...props}></Icon>
