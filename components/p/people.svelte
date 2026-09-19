<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfhx01_3w.css';
import '../../css/l/lwt2_3bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="yfhx01_3w"/><path class="lwt2_3bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:people" {...props}></Icon>
