<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5u01abyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d5u01abyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:chart-pie" {...props}></Icon>
