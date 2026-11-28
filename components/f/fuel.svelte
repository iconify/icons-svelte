<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/edaww7brc.css';
import '../../css/r/rsm9oqubb.css';
import '../../css/t/tpaohmzto.css';
import '../../css/m/mkbjaojxf.css';
import '../../css/m/mlkolobon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="edaww7brc"/><path class="rsm9oqubb"/><path class="tpaohmzto"/><path class="mkbjaojxf"/><path class="mlkolobon"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fuel" {...props}></Icon>
