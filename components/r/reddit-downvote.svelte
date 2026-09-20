<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fulnzej7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fulnzej7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reddit-downvote" {...props}></Icon>
