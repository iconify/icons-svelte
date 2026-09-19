<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-8grfeom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w-8grfeom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chart-gantt" {...props}></Icon>
