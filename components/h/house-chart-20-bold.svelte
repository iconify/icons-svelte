<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmgp-hp4m.css';
import '../../css/u/ufwwjcb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rmgp-hp4m"/><path class="ufwwjcb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-chart-20-bold" {...props}></Icon>
