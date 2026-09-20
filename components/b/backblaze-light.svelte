<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4p59zv7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s4p59zv7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:backblaze-light" {...props}></Icon>
