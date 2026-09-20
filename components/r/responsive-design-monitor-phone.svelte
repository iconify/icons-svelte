<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/l3q2vmw4r.css';
import '../../css/u/ufc6d3x9p.css';
import '../../css/y/yiq1rruyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="l3q2vmw4r"/><path class="ufc6d3x9p"/><path class="yiq1rruyu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:responsive-design-monitor-phone" {...props}></Icon>
