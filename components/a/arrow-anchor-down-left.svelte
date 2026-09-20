<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsvmkibba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tsvmkibba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:arrow-anchor-down-left" {...props}></Icon>
