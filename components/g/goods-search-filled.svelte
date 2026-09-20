<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv5pi-bzy.css';
import '../../css/c/crj_bc0sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iv5pi-bzy"/><path clip-rule="evenodd" class="crj_bc0sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:goods-search-filled" {...props}></Icon>
