<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynbx3b35w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynbx3b35w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-pos-refresh-outline" {...props}></Icon>
