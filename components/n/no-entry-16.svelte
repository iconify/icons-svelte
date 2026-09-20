<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xptn6ibfq.css';
import '../../css/v/voqlvbrhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xptn6ibfq"/><path class="voqlvbrhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:no-entry-16" {...props}></Icon>
