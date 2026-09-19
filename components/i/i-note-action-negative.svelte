<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bg3v29b8u.css';
import '../../css/n/nhdmkwpcm.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsINoteActionNegative0)" class="cuyn6tgcc"><path class="bg3v29b8u"/><path clip-rule="evenodd" class="nhdmkwpcm"/></g><defs><clipPath id="healthiconsINoteActionNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:i-note-action-negative" {...props}></Icon>
