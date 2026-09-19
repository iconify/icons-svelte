<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo7aw631a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xo7aw631a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:rectangle-xmark" {...props}></Icon>
