<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdpvm3rmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rdpvm3rmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:paste" {...props}></Icon>
