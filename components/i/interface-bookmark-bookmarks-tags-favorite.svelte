<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmlcmxzsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tmlcmxzsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-bookmark-bookmarks-tags-favorite" {...props}></Icon>
