<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1olmu0oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a1olmu0oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:itinerary" {...props}></Icon>
