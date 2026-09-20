<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w_fj7nvsb.css';
import '../../css/g/g6y_nx8ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w_fj7nvsb"/><path clip-rule="evenodd" class="g6y_nx8ig"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:money-bill-coin-filled" {...props}></Icon>
