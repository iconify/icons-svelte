<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkkc8mbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rkkc8mbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-365-dark" {...props}></Icon>
