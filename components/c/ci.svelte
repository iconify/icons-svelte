<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qqa_bcb1r.css';
import '../../css/l/lyeaxac2j.css';
import '../../css/p/pmz80t_au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qqa_bcb1r"/><path class="lyeaxac2j"/><path class="pmz80t_au"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:ci" {...props}></Icon>
