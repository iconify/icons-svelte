<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dw9quyb8n.css';
import '../../css/w/wbknnx6bq.css';
import '../../css/x/xoczt_b8w.css';
import '../../css/d/dqty3c3-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dw9quyb8n"/><path class="wbknnx6bq"/><path class="xoczt_b8w"/><path class="dqty3c3-r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:advertising-ad-browser" {...props}></Icon>
