<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km2fl-ght.css';
import '../../css/h/hu39vd16s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="km2fl-ght"/><path class="hu39vd16s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-step-20" {...props}></Icon>
