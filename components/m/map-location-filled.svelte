<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw_48sfjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw_48sfjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-location-filled" {...props}></Icon>
