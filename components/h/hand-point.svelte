<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh80sfblh.css';
import '../../css/t/t7bv4xpss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kh80sfblh"/><path class="t7bv4xpss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:hand-point" {...props}></Icon>
