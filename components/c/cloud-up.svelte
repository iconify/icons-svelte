<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mlx2oubwz.css';
import '../../css/i/ih154-0ss.css';
import '../../css/y/ysed92b4j.css';
import '../../css/k/kcd5utbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mlx2oubwz"/><path class="ih154-0ss"/><path class="ysed92b4j"/><path class="kcd5utbru"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:cloud-up" {...props}></Icon>
