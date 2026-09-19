<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxdnbvbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pxdnbvbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:discriminating-concentration-bioassays" {...props}></Icon>
