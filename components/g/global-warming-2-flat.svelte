<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r8m1a9bnl.css';
import '../../css/t/tkkn2dmyr.css';
import '../../css/u/uf9udxo6b.css';
import '../../css/c/cgu1-bc6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r8m1a9bnl"/><path class="tkkn2dmyr"/><path class="uf9udxo6b"/><path class="cgu1-bc6z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:global-warming-2-flat" {...props}></Icon>
