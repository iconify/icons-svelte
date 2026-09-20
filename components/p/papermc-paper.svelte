<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n73j_hptb.css';
import '../../css/t/tvrvbjbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n73j_hptb"/><path class="tvrvbjbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermc-paper" {...props}></Icon>
