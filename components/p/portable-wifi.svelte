<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t41rjyaqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":400};
const content = `<path class="t41rjyaqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:portable-wifi" {...props}></Icon>
