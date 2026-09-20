<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyp46zrds.css';
import '../../css/s/sor599b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zyp46zrds"/><path class="sor599b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-messages-light" {...props}></Icon>
