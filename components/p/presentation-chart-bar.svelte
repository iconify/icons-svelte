<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oibudcbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oibudcbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:presentation-chart-bar" {...props}></Icon>
