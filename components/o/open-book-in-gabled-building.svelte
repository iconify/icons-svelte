<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb4f1fz8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eb4f1fz8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-book-in-gabled-building" {...props}></Icon>
