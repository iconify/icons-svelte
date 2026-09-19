<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4ksah0px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r4ksah0px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:book-closed-stroke-16" {...props}></Icon>
