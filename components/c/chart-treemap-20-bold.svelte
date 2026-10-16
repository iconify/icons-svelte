<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_3tybcwd.css';
import '../../css/u/u3mp5lqgi.css';
import '../../css/x/x-3aazb-g.css';
import '../../css/e/enwjp7ebc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l_3tybcwd"/><path class="u3mp5lqgi"/><path class="x-3aazb-g"/><path class="enwjp7ebc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-treemap-20-bold" {...props}></Icon>
