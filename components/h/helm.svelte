<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-u9xrknx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b-u9xrknx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:helm" {...props}></Icon>
