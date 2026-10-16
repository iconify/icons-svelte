<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfnsa8bub.css';
import '../../css/u/u6s26w-eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rfnsa8bub"/><path class="u6s26w-eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:aquifer-20-bold" {...props}></Icon>
