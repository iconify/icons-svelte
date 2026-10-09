<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv_v6xgdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rv_v6xgdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-loss-20" {...props}></Icon>
