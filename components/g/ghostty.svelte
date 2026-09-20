<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dosrg5bml.css';
import '../../css/d/djaim6bic.css';
import '../../css/m/mp4dc4cxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dosrg5bml"/><path class="djaim6bic"/><path class="mp4dc4cxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ghostty" {...props}></Icon>
