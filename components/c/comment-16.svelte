<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4ismqc7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j4ismqc7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:comment-16" {...props}></Icon>
