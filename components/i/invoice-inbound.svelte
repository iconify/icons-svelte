<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn9e5mbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dn9e5mbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-inbound" {...props}></Icon>
