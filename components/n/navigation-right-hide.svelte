<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6g0jxblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="p6g0jxblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:navigation-right-hide" {...props}></Icon>
