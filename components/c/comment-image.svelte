<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-1qd4bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="f-1qd4bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:comment-image" {...props}></Icon>
