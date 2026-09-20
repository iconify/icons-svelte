<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omesdvb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="omesdvb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reddit-upvote-light" {...props}></Icon>
