<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz9572bcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bz9572bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-upload" {...props}></Icon>
