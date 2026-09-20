<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsdibsc_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsdibsc_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flight-land-line" {...props}></Icon>
