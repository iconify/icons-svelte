<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0gwnbb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b0gwnbb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-left-stroke-16" {...props}></Icon>
