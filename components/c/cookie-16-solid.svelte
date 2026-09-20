<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij64onw0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ij64onw0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cookie-16-solid" {...props}></Icon>
