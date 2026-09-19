<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq1o3oben.css';
import '../../css/q/qzsos-3ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iq1o3oben"/><path class="qzsos-3ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:evernote" {...props}></Icon>
