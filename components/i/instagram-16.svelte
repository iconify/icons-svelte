<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d95zib8im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d95zib8im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:instagram-16" {...props}></Icon>
