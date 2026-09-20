<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2dsus3eh.css';
import '../../css/m/mh2gjorsd.css';
import '../../css/h/h7vs4zvyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e2dsus3eh"/><path class="mh2gjorsd"/><path class="h7vs4zvyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bitwarden-portal" {...props}></Icon>
