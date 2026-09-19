<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdj82wxwd.css';
import '../../css/k/kr_8yqlhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xdj82wxwd"/><path class="kr_8yqlhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bag-handle-outline" {...props}></Icon>
