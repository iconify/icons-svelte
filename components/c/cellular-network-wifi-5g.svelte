<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/h/h2ebchlrj.css';
import '../../css/b/bmlc_mb5j.css';
import '../../css/h/hoic_wbnl.css';
import '../../css/k/kcfesybjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="h2ebchlrj"/><path class="bmlc_mb5j"/><path class="hoic_wbnl"/><path class="kcfesybjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:cellular-network-wifi-5g" {...props}></Icon>
