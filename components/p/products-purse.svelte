<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hmzy87vxc.css';
import '../../css/s/sif8embcq.css';
import '../../css/j/jft-c8bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hmzy87vxc"/><path class="sif8embcq"/><path class="jft-c8bfx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:products-purse" {...props}></Icon>
