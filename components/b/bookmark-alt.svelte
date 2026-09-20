<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbfurgbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="xbfurgbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bookmark-alt" {...props}></Icon>
