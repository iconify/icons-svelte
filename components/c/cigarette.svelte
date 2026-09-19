<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4o3fs57g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="j4o3fs57g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cigarette" {...props}></Icon>
