<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5dz5-btu.css';
import '../../css/e/e8z4a313a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r5dz5-btu"/><path class="e8z4a313a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badge-20" {...props}></Icon>
