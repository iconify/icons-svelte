<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugoumwb4c.css';
import '../../css/c/cfmtxnb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ugoumwb4c"/><path class="cfmtxnb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chatbubbles-sharp" {...props}></Icon>
