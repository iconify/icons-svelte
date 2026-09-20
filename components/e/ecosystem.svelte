<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msnkf_bkn.css';
import '../../css/k/kq5sxkbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="msnkf_bkn"/><path class="kq5sxkbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:ecosystem" {...props}></Icon>
