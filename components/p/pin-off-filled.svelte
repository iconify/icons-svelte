<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymol9uw0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymol9uw0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pin-off-filled" {...props}></Icon>
