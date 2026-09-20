<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xzb_z2bum.css';
import '../../css/m/m5f5s512t.css';
import '../../css/g/guzqnlbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xzb_z2bum"/><path class="m5f5s512t"/><path class="guzqnlbhl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:microprocessor-computer-chip-search" {...props}></Icon>
