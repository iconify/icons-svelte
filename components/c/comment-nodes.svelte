<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b13n3cccp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="b13n3cccp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:comment-nodes" {...props}></Icon>
