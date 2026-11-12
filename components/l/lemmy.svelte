<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfth_183n.css';
import '../../css/h/h4y9kdbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rfth_183n"/><path class="h4y9kdbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lemmy" {...props}></Icon>
