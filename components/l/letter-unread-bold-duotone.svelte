<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hj4zhi7dw.css';
import '../../css/r/rublczxpb.css';
import '../../css/h/h7cjiyxej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hj4zhi7dw"/><path class="rublczxpb"/><path class="h7cjiyxej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:letter-unread-bold-duotone" {...props}></Icon>
