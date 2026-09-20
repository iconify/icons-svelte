<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/e/e7ra0203t.css';
import '../../css/l/l_oo4cchq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="e7ra0203t"/><path class="l_oo4cchq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bookmark-circle" {...props}></Icon>
