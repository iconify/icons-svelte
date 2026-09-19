<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2zyaudgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="r2zyaudgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:box-open" {...props}></Icon>
