<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfa6qkixq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yfa6qkixq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-export" {...props}></Icon>
