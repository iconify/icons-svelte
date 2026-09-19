<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc46xob6r.css';
import '../../css/i/ilhwmcbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lc46xob6r"/><path class="ilhwmcbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-bear-right-01-filled" {...props}></Icon>
