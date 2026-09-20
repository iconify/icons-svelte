<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7sif6b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z7sif6b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:exclamation-mark-circle-solid" {...props}></Icon>
