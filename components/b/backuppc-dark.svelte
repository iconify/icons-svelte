<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt75vhbsg.css';
import '../../css/y/y4cd3rkme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kt75vhbsg"/><path class="y4cd3rkme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:backuppc-dark" {...props}></Icon>
