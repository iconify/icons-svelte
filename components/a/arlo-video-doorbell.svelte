<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm_dlq0xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm_dlq0xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:arlo-video-doorbell" {...props}></Icon>
