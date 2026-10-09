<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnl7id0ua.css';
import '../../css/k/k4v56fbhg.css';
import '../../css/c/ci9x7ub2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vnl7id0ua"/><path class="k4v56fbhg"/><path class="ci9x7ub2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-pump-water-20" {...props}></Icon>
