<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyxxv8bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zyxxv8bah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:daemon-sync-light" {...props}></Icon>
