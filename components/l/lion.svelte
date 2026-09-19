<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l8oli-e-g.css';
import '../../css/n/nf2-fkbdx.css';
import '../../css/v/v9vsj_bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l8oli-e-g"/><path clip-rule="evenodd" class="nf2-fkbdx"/><path clip-rule="evenodd" class="v9vsj_bvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lion" {...props}></Icon>
