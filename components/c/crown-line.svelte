<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d777w44ag.css';
import '../../css/c/c9yx--bxi.css';
import '../../css/z/zpen0xb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="d777w44ag"/><circle class="c9yx--bxi"/><path class="zpen0xb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:crown-line" {...props}></Icon>
