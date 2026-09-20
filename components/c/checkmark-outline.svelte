<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba3fxrbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ba3fxrbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:checkmark-outline" {...props}></Icon>
