<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-ttanbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m-ttanbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-funnel-20-bold" {...props}></Icon>
