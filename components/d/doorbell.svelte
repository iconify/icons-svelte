<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz69jibxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz69jibxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:doorbell" {...props}></Icon>
