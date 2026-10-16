<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is2wtacnu.css';
import '../../css/w/wqs95_b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="is2wtacnu"/><path class="wqs95_b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-pie-slice-20-bold" {...props}></Icon>
