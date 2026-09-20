<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/ltmwlr7si.css';
import '../../css/j/jxcqzgbap.css';
import '../../css/p/pxku7lbxz.css';
import '../../css/t/ti5kg_b8s.css';
import '../../css/d/dwpi1dbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ltmwlr7si"/><path class="jxcqzgbap"/><path class="pxku7lbxz"/><path class="ti5kg_b8s"/><path class="dwpi1dbbm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:keyboard-wireless" {...props}></Icon>
