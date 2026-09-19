<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zl_c1zqrx.css';
import '../../css/u/unud4-b6i.css';
import '../../css/u/uha_3w82g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="zl_c1zqrx"/><path class="unud4-b6i"/><path class="uha_3w82g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:building" {...props}></Icon>
