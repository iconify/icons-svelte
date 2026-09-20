<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqgil-9zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iqgil-9zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chevron-right-small" {...props}></Icon>
