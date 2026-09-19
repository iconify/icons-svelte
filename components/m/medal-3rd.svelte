<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-ughjblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p-ughjblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:medal-3rd" {...props}></Icon>
