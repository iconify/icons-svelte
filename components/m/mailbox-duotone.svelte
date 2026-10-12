<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a_p3zv2qb.css';
import '../../css/y/yyeznrbrj.css';
import '../../css/r/rh9k3tbfh.css';
import '../../css/t/t7espybpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a_p3zv2qb"/><path class="yyeznrbrj"/><path class="rh9k3tbfh"/><path class="t7espybpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mailbox-duotone" {...props}></Icon>
