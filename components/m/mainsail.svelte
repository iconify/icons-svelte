<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8-z-4b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q8-z-4b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mainsail" {...props}></Icon>
