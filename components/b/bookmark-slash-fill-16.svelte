<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k14xt0b7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k14xt0b7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bookmark-slash-fill-16" {...props}></Icon>
