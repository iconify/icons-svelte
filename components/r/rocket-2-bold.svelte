<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/whvaa_bdm.css';
import '../../css/y/yp--lsbio.css';
import '../../css/d/d_3_miv7p.css';
import '../../css/e/ed_lewb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="whvaa_bdm"/><path class="yp--lsbio"/><path class="d_3_miv7p"/><path clip-rule="evenodd" class="ed_lewb2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rocket-2-bold" {...props}></Icon>
