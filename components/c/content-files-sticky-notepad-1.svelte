<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi01iacmk.css';
import '../../css/r/rghyt8iyb.css';
import '../../css/z/zqb02xggr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bi01iacmk"/><path class="rghyt8iyb"/><path class="zqb02xggr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-sticky-notepad-1" {...props}></Icon>
