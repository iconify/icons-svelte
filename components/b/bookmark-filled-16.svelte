<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xworeqbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xworeqbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bookmark-filled-16" {...props}></Icon>
