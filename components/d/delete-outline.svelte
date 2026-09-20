<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7ovy1b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e7ovy1b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:delete-outline" {...props}></Icon>
