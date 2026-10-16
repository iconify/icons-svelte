<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ske3-m5ph.css';
import '../../css/s/scl-k_bqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ske3-m5ph"/><path class="scl-k_bqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:face-shield-20-bold" {...props}></Icon>
