<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5iirtbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5iirtbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:downvote" {...props}></Icon>
