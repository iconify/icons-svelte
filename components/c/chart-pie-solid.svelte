<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3uhupbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a3uhupbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chart-pie-solid" {...props}></Icon>
