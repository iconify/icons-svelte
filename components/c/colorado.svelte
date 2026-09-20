<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-0ytcb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t-0ytcb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:colorado" {...props}></Icon>
