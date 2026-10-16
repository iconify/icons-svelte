<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvvhovf8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yvvhovf8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-funnel-48-bold" {...props}></Icon>
