<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/ef8pwpb6n.css';
import '../../css/s/sleouwb3s.css';
import '../../css/w/w-asugb8r.css';
import '../../css/e/elikaogpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ef8pwpb6n"/><path class="sleouwb3s"/><path class="w-asugb8r"/><path class="elikaogpc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:history-outline" {...props}></Icon>
