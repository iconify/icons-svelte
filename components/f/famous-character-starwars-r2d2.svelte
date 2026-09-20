<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/o64x2918v.css';
import '../../css/v/v2gvpubcr.css';
import '../../css/g/g_seqxb6b.css';
import '../../css/b/bpod7mzyw.css';
import '../../css/s/sc7p9pb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="o64x2918v"/><path class="v2gvpubcr"/><path class="g_seqxb6b"/><path class="bpod7mzyw"/><path class="sc7p9pb0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:famous-character-starwars-r2d2" {...props}></Icon>
