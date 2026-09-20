<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btoo07bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="btoo07bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:barkeep-light" {...props}></Icon>
