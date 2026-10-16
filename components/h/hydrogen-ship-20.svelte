<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_z7uitjb.css';
import '../../css/v/v2u1wbcfd.css';
import '../../css/t/tvp2jabtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k_z7uitjb"/><path class="v2u1wbcfd"/><path class="tvp2jabtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-ship-20" {...props}></Icon>
