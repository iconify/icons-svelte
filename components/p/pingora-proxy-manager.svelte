<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czfhl0lnw.css';
import '../../css/f/f4wrckbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="czfhl0lnw"/><path class="f4wrckbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pingora-proxy-manager" {...props}></Icon>
