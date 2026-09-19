<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/firpjtj6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="firpjtj6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:interlocking-rings-fill-16" {...props}></Icon>
