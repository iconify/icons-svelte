<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djvtggqsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djvtggqsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:panorama-wide-angle-outline" {...props}></Icon>
