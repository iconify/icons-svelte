<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyf0942nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyf0942nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gesture-swipe-down" {...props}></Icon>
