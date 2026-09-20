<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgrpdcbuo.css';
import '../../css/z/zl1t5ibdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fgrpdcbuo"/><path class="zl1t5ibdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:phone-signal-full" {...props}></Icon>
