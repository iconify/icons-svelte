<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqf4o3-1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqf4o3-1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:calendar-check-2" {...props}></Icon>
