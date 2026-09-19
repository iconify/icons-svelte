<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s75iopu5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s75iopu5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-bookmarks-outline" {...props}></Icon>
