<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrl_9-k9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hrl_9-k9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:file-tray" {...props}></Icon>
