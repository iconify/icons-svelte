<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fosscbcwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fosscbcwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:plus" {...props}></Icon>
