<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeju42bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xeju42bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:location-arrow" {...props}></Icon>
