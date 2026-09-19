<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev-_rkitm.css';
import '../../css/l/lxavlrbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ev-_rkitm"/><path class="lxavlrbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:image-search-alt" {...props}></Icon>
