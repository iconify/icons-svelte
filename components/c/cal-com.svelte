<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrjsy3seb.css';
import '../../css/f/fc0sbw29e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vrjsy3seb"/><path class="fc0sbw29e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cal-com" {...props}></Icon>
