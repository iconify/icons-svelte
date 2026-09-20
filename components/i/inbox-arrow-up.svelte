<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt-9l2bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt-9l2bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:inbox-arrow-up" {...props}></Icon>
