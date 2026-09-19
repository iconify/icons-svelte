<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz3672b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vz3672b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:comment-nodes" {...props}></Icon>
