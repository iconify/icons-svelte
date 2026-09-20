<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t8ir5j57n.css';
import '../../css/v/vm3e4ebcu.css';
import '../../css/t/t2yjsqb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="t8ir5j57n"/><path class="vm3e4ebcu"/><path class="t2yjsqb-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:business-cash-eye" {...props}></Icon>
