<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hgk3nsj2p.css';
import '../../css/h/ho4qdccuy.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsBladderNegative0)" class="cuyn6tgcc"><path class="hgk3nsj2p"/><path clip-rule="evenodd" class="ho4qdccuy"/></g><defs><clipPath id="healthiconsBladderNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:bladder-negative" {...props}></Icon>
