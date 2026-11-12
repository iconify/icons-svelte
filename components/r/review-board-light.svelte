<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkv6y8nxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gkv6y8nxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:review-board-light" {...props}></Icon>
