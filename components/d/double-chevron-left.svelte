<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc2_d5b7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zc2_d5b7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:double-chevron-left" {...props}></Icon>
