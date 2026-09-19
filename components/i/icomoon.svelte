<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv_hd5bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gv_hd5bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:icomoon" {...props}></Icon>
