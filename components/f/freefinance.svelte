<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0ncxjb_s.css';
import '../../css/b/bs_ka8b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v0ncxjb_s"/><path class="bs_ka8b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freefinance" {...props}></Icon>
