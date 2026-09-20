<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbp1jcc3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xbp1jcc3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:round-arrow-2" {...props}></Icon>
