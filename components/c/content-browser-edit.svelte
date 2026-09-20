<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/ariqabb3m.css';
import '../../css/p/p3xi1cbyh.css';
import '../../css/h/hcf_tsbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ariqabb3m"/><path class="p3xi1cbyh"/><path class="hcf_tsbst"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:content-browser-edit" {...props}></Icon>
