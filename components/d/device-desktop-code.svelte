<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipd8iub8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipd8iub8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-code" {...props}></Icon>
