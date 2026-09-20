<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljdd0lbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ljdd0lbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:log" {...props}></Icon>
