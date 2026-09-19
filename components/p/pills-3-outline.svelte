<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/j/js99oebrf.css';
import '../../css/r/rz6frnslz.css';
import '../../css/i/i7udtsooe.css';
import '../../css/q/qegdji1er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="js99oebrf"/><path class="rz6frnslz"/><path class="i7udtsooe"/><path class="qegdji1er"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pills-3-outline" {...props}></Icon>
