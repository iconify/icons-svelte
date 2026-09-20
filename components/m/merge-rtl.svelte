<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1nv75n_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l1nv75n_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:merge-rtl" {...props}></Icon>
