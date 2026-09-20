<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhmb8zbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lhmb8zbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-envelope-right-with-dollar" {...props}></Icon>
