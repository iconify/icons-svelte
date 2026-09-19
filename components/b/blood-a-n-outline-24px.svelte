<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bw8g9_b8v.css';
import '../../css/l/l15qbrbre.css';
import '../../css/v/v4s2axqse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bw8g9_b8v"/><path class="l15qbrbre"/><path clip-rule="evenodd" class="v4s2axqse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-a-n-outline-24px" {...props}></Icon>
