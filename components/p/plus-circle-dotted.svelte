<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0oyi7b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b0oyi7b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:plus-circle-dotted" {...props}></Icon>
