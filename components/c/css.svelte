<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fejgivb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fejgivb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:css" {...props}></Icon>
