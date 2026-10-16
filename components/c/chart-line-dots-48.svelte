<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utf77lbef.css';
import '../../css/b/bm1aiubys.css';
import '../../css/h/h6bsihbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="utf77lbef"/><path class="bm1aiubys"/><path class="h6bsihbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-line-dots-48" {...props}></Icon>
