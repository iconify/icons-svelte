<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/as6_xp3_v.css';
import '../../css/c/ciq1v2bio.css';
import '../../css/d/dup_gbchp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="as6_xp3_v"/><path class="ciq1v2bio"/><path clip-rule="evenodd" class="dup_gbchp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:globe2-duotone" {...props}></Icon>
