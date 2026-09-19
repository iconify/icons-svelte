<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-4khpb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="r-4khpb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:report-library-mirrored" {...props}></Icon>
