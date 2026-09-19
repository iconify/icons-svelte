<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz44xsv-i.css';
import '../../css/i/i6iu0p2uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bz44xsv-i"/><path class="i6iu0p2uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-bookmarks" {...props}></Icon>
