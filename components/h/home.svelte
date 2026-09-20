<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6r7svz_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t6r7svz_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:home" {...props}></Icon>
