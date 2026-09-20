<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/i4d-utb-k.css';
import '../../css/v/vfu_14b9n.css';
import '../../css/z/zf1rafb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="i4d-utb-k"/><path class="vfu_14b9n"/><path class="zf1rafb_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:charging-flash-wireless" {...props}></Icon>
