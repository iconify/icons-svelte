<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwugou01a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwugou01a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-area" {...props}></Icon>
