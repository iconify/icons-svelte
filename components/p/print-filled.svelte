<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4ltur30r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b4ltur30r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:print-filled" {...props}></Icon>
