<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxk0zwqnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yxk0zwqnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kagi-light" {...props}></Icon>
