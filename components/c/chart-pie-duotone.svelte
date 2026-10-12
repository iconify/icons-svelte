<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f2lcyxzyt.css';
import '../../css/r/rz0q3eb5l.css';
import '../../css/u/u1dt7ccjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f2lcyxzyt"/><path class="rz0q3eb5l"/><path class="u1dt7ccjc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:chart-pie-duotone" {...props}></Icon>
