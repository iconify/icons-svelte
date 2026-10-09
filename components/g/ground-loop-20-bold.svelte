<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4lhl3b6q.css';
import '../../css/l/lfzfbp_8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q4lhl3b6q"/><path class="lfzfbp_8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ground-loop-20-bold" {...props}></Icon>
