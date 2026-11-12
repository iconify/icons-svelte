<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd4o_acha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bd4o_acha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:emoncms-light" {...props}></Icon>
