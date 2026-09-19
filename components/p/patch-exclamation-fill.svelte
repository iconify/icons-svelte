<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzqu9x0yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rzqu9x0yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:patch-exclamation-fill" {...props}></Icon>
