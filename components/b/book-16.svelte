<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcy60_bxj.css';
import '../../css/d/dw8a25bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rcy60_bxj"/><path clip-rule="evenodd" class="dw8a25bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:book-16" {...props}></Icon>
