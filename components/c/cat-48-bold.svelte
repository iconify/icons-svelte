<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk_lpbr1e.css';
import '../../css/c/cmf_awb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lk_lpbr1e"/><path class="cmf_awb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cat-48-bold" {...props}></Icon>
