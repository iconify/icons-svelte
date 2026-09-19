<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rje_9tbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rje_9tbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:missile" {...props}></Icon>
