<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wg9lcmw6v.css';
import '../../css/c/c7vu4eb-g.css';
import '../../css/k/kbndj12cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wg9lcmw6v"/><path clip-rule="evenodd" class="c7vu4eb-g"/><path class="kbndj12cr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:flashlight-on" {...props}></Icon>
