<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrg2y8b_v.css';
import '../../css/e/e0a-jqb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hrg2y8b_v"/><path class="e0a-jqb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:city-skyline-20-bold" {...props}></Icon>
