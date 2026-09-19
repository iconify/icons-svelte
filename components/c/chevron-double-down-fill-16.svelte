<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1m6q9zqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p1m6q9zqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-double-down-fill-16" {...props}></Icon>
