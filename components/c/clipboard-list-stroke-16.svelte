<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em2davzvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="em2davzvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clipboard-list-stroke-16" {...props}></Icon>
