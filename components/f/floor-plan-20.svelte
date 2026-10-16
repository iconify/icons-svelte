<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep1rdvbyo.css';
import '../../css/n/n6y0u1blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ep1rdvbyo"/><path class="n6y0u1blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:floor-plan-20" {...props}></Icon>
