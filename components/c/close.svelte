<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh0s2-9xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kh0s2-9xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:close" {...props}></Icon>
