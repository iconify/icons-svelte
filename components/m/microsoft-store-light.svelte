<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft090pbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ft090pbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-store-light" {...props}></Icon>
