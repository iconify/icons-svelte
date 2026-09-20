<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygh_cx1if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ygh_cx1if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mail-search-solid" {...props}></Icon>
