<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2os1ubay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i2os1ubay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:pie-chart" {...props}></Icon>
