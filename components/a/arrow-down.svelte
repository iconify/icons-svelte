<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i663cybmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i663cybmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:arrow-down" {...props}></Icon>
