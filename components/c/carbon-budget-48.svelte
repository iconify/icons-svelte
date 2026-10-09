<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj2y6_b-x.css';
import '../../css/b/bew7-otna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dj2y6_b-x"/><path class="bew7-otna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-budget-48" {...props}></Icon>
