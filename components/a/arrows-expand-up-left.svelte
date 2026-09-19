<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jonn9cbay.css';
import '../../css/s/s0kk7bcyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jonn9cbay"/><path clip-rule="evenodd" class="s0kk7bcyp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrows-expand-up-left" {...props}></Icon>
