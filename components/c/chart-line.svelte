<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr25z3bhd.css';
import '../../css/d/d5cn6-g7r.css';
import '../../css/g/g0_j010xc.css';
import '../../css/t/tok5ds4az.css';
import '../../css/t/tkz0t1bdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr25z3bhd wm-shadow"/><path class="d5cn6-g7r wm-k"/><path class="g0_j010xc wm-k"/><path class="tok5ds4az wm-a"/><path class="tkz0t1bdz wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:chart-line" {...props}></Icon>
