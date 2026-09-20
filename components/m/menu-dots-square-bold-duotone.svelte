<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y6-b8lbmz.css';
import '../../css/y/y-xxqpbcl.css';
import '../../css/o/o3omre-is.css';
import '../../css/g/g7m_9fb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y6-b8lbmz"/><path class="y-xxqpbcl"/><path class="o3omre-is"/><path class="g7m_9fb1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:menu-dots-square-bold-duotone" {...props}></Icon>
