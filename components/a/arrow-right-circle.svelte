<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ajr_bsq.css';
import '../../css/u/ufvpeacwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="f6ajr_bsq"/><path clip-rule="evenodd" class="ufvpeacwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-right-circle" {...props}></Icon>
