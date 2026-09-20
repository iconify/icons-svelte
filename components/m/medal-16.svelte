<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxq3-eb3u.css';
import '../../css/x/x3ezi_wmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bxq3-eb3u"/><path clip-rule="evenodd" class="x3ezi_wmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:medal-16" {...props}></Icon>
