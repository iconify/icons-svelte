<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/himeb8x8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="himeb8x8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:book-open" {...props}></Icon>
