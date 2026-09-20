<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-x7yjbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i-x7yjbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:certificate-exclamation-filled" {...props}></Icon>
