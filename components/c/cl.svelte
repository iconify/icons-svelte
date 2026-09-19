<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/c/clv_0rxpg.css';
import '../../css/a/ahb3szrou.css';
import '../../css/y/yg27cxuxs.css';
import '../../css/r/rxtygbq0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="clv_0rxpg"/><path class="ahb3szrou"/><path class="yg27cxuxs"/><path class="rxtygbq0g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:cl" {...props}></Icon>
