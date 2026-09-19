<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skuv7-l6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="skuv7-l6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:list-check" {...props}></Icon>
