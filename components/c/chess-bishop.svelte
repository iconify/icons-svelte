<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb52ahb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yb52ahb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:chess-bishop" {...props}></Icon>
