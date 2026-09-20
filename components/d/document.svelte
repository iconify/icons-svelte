<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwq7_02iq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zwq7_02iq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:document" {...props}></Icon>
