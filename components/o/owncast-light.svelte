<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jan45d7nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jan45d7nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:owncast-light" {...props}></Icon>
