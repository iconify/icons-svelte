<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbxa1bb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wbxa1bb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:library" {...props}></Icon>
