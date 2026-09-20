<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ito3gy.css';
import '../../css/i/iw1iew.css';
import '../../css/m/mz7t6h.css';
import '../../css/s/so-from-40.css';
import '../../css/f/fade-to-1.css';
import '../../css/d/d-stq6uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ito3gy iw1iew"/><path class="iw1iew mz7t6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:round-360" {...props}></Icon>
