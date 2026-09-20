<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l5ddg53rf.css';
import '../../css/l/lm7_ujbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="l5ddg53rf"/><circle class="lm7_ujbrk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:fiverr" {...props}></Icon>
