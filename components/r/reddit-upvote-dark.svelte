<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjb7rdlib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zjb7rdlib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reddit-upvote-dark" {...props}></Icon>
