<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/spya73b4x.css';
import '../../css/c/c9v8bbnei.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsDizzyNegative0)" clip-rule="evenodd" class="n1lsf0bnc"><path class="spya73b4x"/><path class="c9v8bbnei"/></g><defs><clipPath id="healthiconsDizzyNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:dizzy-negative" {...props}></Icon>
