<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh-es2avx.css';
import '../../css/x/x8lr6rehc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xh-es2avx"/><path class="x8lr6rehc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-off-20-bold" {...props}></Icon>
