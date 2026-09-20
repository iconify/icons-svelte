<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lxnzn9nmw.css';
import '../../css/j/j3-m1tbbc.css';
import '../../css/a/abx110vzg.css';
import '../../css/x/xjsotyb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lxnzn9nmw"/><path class="j3-m1tbbc"/><path class="abx110vzg"/><path class="xjsotyb9a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chart-square-bold-duotone" {...props}></Icon>
