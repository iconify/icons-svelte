<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8r3v9d3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v8r3v9d3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:bell-solid" {...props}></Icon>
