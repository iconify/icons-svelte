<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xd6pe9bvg.css';
import '../../css/s/sg5u4cmdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xd6pe9bvg"/><path clip-rule="evenodd" class="sg5u4cmdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:eftpos-alt" {...props}></Icon>
