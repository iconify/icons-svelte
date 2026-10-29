<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqnh6ybes.css';
import '../../css/t/th1hqrxri.css';
import '../../css/w/wx0602c_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqnh6ybes wm-shadow"/><path class="th1hqrxri wm-k"/><path class="wm-k wx0602c_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:arrow-left" {...props}></Icon>
