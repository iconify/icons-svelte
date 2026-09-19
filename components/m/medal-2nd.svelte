<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udrja85vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="udrja85vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:medal-2nd" {...props}></Icon>
