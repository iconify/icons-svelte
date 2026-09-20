<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbrxewtok.css';
import '../../css/i/iw0mf28vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bbrxewtok"/><path class="iw0mf28vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kherad" {...props}></Icon>
