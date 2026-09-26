<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b2vvr6bvh.css';
import '../../css/v/v_xbae9wh.css';
import '../../css/l/l_g5nnb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b2vvr6bvh"/><path class="v_xbae9wh"/><path class="l_g5nnb8p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-bottom-open-line-duotone" {...props}></Icon>
