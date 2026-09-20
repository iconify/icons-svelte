<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/ikl747bil.css';
import '../../css/o/ovuwqmcap.css';
import '../../css/d/dkb-t3bph.css';
import '../../css/z/znhoneb8n.css';
import '../../css/a/as5ptpbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ikl747bil"/><path class="ovuwqmcap"/><path class="dkb-t3bph"/><path class="znhoneb8n"/><path class="as5ptpbfk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:accounting-calculator" {...props}></Icon>
