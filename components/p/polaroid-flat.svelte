<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t6a4tpbqc.css';
import '../../css/i/ij7j57b7c.css';
import '../../css/x/xsjxoiu5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="t6a4tpbqc"/><path class="ij7j57b7c"/><path class="xsjxoiu5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:polaroid-flat" {...props}></Icon>
