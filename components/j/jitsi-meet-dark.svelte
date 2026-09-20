<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8z549mku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i8z549mku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jitsi-meet-dark" {...props}></Icon>
