<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujopaebxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ujopaebxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quick-reference-light" {...props}></Icon>
