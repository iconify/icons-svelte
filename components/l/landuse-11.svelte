<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om_becc8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="om_becc8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:landuse-11" {...props}></Icon>
