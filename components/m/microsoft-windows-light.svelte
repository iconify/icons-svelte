<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d45cpc0pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d45cpc0pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-windows-light" {...props}></Icon>
