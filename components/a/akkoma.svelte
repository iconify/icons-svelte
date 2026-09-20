<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc5trhbqj.css';
import '../../css/p/p6ca8ub5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dc5trhbqj"/><path class="p6ca8ub5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:akkoma" {...props}></Icon>
