<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s1tgnev_z.css';
import '../../css/h/hgjtjbt2w.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsAmbulatoryClinicNegative0)" class="cuyn6tgcc"><path class="s1tgnev_z"/><path clip-rule="evenodd" class="hgjtjbt2w"/></g><defs><clipPath id="healthiconsAmbulatoryClinicNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ambulatory-clinic-negative" {...props}></Icon>
