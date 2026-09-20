<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/exdmtsbst.css';
import '../../css/c/cq0pnj2xi.css';
import '../../css/u/utvuz8bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="exdmtsbst"/><path class="cq0pnj2xi"/><path class="utvuz8bri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:meeting-user-man-stress" {...props}></Icon>
