<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irsl63llt.css';
import '../../css/n/nvwx11b3c.css';
import '../../css/n/n4xv7q49k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="irsl63llt"/><path class="nvwx11b3c"/><path class="n4xv7q49k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:file-portal-light" {...props}></Icon>
