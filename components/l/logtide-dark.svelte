<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0vr9-v0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w0vr9-v0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:logtide-dark" {...props}></Icon>
