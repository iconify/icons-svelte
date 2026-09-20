<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n351nwb6r.css';
import '../../css/z/zw_v3acsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n351nwb6r"/><path class="zw_v3acsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:hospital-symbol" {...props}></Icon>
