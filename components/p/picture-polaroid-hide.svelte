<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xsxyw_szs.css';
import '../../css/o/ouxwt8bby.css';
import '../../css/p/pyr87bb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xsxyw_szs"/><path class="ouxwt8bby"/><path class="pyr87bb_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:picture-polaroid-hide" {...props}></Icon>
