<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re2vbxbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="re2vbxbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:emoji-laughing-fill" {...props}></Icon>
