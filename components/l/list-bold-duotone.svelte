<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t6tl7ybcd.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/q/qigovot_c.css';
import '../../css/v/v-s_f4e2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="t6tl7ybcd"/><g class="mc2zb0bvp"><path class="qigovot_c"/><path class="v-s_f4e2d"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-bold-duotone" {...props}></Icon>
