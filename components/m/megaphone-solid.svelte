<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op9huqmep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="op9huqmep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:megaphone-solid" {...props}></Icon>
