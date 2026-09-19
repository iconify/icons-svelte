<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrkaw1ncp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wrkaw1ncp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:emoji-grin-fill" {...props}></Icon>
