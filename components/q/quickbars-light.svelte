<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df8texbdg.css';
import '../../css/e/eg-j-vy9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="df8texbdg"/><path class="eg-j-vy9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quickbars-light" {...props}></Icon>
