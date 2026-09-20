<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1lneq22n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j1lneq22n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:calendar-solid" {...props}></Icon>
