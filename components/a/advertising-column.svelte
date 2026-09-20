<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inujsab6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="inujsab6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:advertising-column" {...props}></Icon>
