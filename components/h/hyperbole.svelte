<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgzbchhed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgzbchhed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hyperbole" {...props}></Icon>
