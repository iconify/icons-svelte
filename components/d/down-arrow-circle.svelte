<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0aqzmb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w0aqzmb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:down-arrow-circle" {...props}></Icon>
