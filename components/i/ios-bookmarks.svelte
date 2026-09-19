<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4zgz8bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y4zgz8bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-bookmarks" {...props}></Icon>
