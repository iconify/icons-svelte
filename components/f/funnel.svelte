<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp939ybwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lp939ybwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:funnel" {...props}></Icon>
