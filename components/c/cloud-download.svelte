<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4qnazbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x4qnazbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:cloud-download" {...props}></Icon>
