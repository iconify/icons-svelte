<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_j5rbcgv.css';
import '../../css/x/xw_k98btt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v_j5rbcgv"/><path class="xw_k98btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:microwave-20" {...props}></Icon>
