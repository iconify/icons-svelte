<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haoji6kic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haoji6kic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:battery-critical" {...props}></Icon>
