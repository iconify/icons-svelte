<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4l-yfbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p4l-yfbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-right-outline" {...props}></Icon>
