<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na8uue77l.css';
import '../../css/d/d8n319blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="na8uue77l"/><path class="d8n319blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-drive-light" {...props}></Icon>
