<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlq2vxlgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlq2vxlgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-street-view" {...props}></Icon>
