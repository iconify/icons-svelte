<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u1gzkvr5a.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/h/hfqsmecof.css';
import '../../css/q/qb_h7yw5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="u1gzkvr5a"/><g class="mc2zb0bvp"><path class="hfqsmecof"/><path class="qb_h7yw5a"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-to-top-right-bold-duotone" {...props}></Icon>
