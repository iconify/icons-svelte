<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umounmz6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="umounmz6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:map-pin-solid" {...props}></Icon>
