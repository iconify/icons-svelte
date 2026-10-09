<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_1rdccum.css';
import '../../css/m/mptrtbrij.css';
import '../../css/q/qi6_u5bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t_1rdccum"/><path class="mptrtbrij"/><path class="qi6_u5bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flywheel-20-bold" {...props}></Icon>
