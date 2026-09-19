<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl1-n-b-w.css';
import '../../css/k/k5vk-bbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bl1-n-b-w"/><path class="k5vk-bbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:currency" {...props}></Icon>
