<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r07j-kbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r07j-kbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:currency-dollar" {...props}></Icon>
