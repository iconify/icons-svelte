<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmfkg_j2b.css';
import '../../css/z/z0r2h759q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="mmfkg_j2b"/><path class="z0r2h759q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cloud-check" {...props}></Icon>
