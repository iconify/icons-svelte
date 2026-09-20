<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow7g2ackt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ow7g2ackt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-heart" {...props}></Icon>
