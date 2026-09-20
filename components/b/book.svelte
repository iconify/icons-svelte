<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf5u_qbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zf5u_qbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:book" {...props}></Icon>
