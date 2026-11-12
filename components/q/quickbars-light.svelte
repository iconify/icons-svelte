<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df8texbdg.css';
import '../../css/q/q0j4_mbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="df8texbdg"/><path class="q0j4_mbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quickbars-light" {...props}></Icon>
