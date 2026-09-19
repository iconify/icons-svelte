<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rfnphpyms.css';
import '../../css/e/ekf464gcd.css';
import '../../css/r/rb4mrx5mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="rfnphpyms"/><path class="ekf464gcd"/><path clip-rule="evenodd" class="rb4mrx5mp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-a-p-24px" {...props}></Icon>
