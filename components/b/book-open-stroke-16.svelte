<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y04prtbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y04prtbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:book-open-stroke-16" {...props}></Icon>
