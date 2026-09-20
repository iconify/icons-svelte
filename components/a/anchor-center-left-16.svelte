<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkm0taczv.css';
import '../../css/x/xm74jkbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gkm0taczv"/><path class="xm74jkbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:anchor-center-left-16" {...props}></Icon>
