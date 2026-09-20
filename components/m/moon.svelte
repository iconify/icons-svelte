<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9hy1yk1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l9hy1yk1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:moon" {...props}></Icon>
