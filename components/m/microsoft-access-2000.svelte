<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sibkcjb8c.css';
import '../../css/i/ii43a9b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sibkcjb8c"/><path class="ii43a9b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-access-2000" {...props}></Icon>
