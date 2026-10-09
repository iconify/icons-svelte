<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty8a93bmr.css';
import '../../css/r/rzu6pacwb.css';
import '../../css/p/pvt3vvkbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ty8a93bmr"/><path class="rzu6pacwb"/><path class="pvt3vvkbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-lay-vessel-48-bold" {...props}></Icon>
