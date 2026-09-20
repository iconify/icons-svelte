<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnbv4uh6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnbv4uh6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:content-save-off" {...props}></Icon>
