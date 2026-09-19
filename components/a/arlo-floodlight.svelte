<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed9oapbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed9oapbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:arlo-floodlight" {...props}></Icon>
