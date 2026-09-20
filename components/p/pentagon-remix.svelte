<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw_gh8mfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zw_gh8mfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pentagon-remix" {...props}></Icon>
