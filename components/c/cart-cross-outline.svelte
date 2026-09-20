<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j7vq9lbhd.css';
import '../../css/x/x59fuv1nw.css';
import '../../css/p/p-nzwk9jc.css';
import '../../css/g/gewiseacf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j7vq9lbhd"/><path clip-rule="evenodd" class="x59fuv1nw"/><path clip-rule="evenodd" class="p-nzwk9jc"/><path clip-rule="evenodd" class="gewiseacf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-cross-outline" {...props}></Icon>
