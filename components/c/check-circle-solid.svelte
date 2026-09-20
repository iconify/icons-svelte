<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y64eztbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y64eztbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:check-circle-solid" {...props}></Icon>
