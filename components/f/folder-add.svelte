<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o49e5qy4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o49e5qy4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:folder-add" {...props}></Icon>
