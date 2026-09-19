<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4u_y1bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w4u_y1bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:church" {...props}></Icon>
