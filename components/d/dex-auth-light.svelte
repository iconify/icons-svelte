<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwckj7bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rwckj7bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dex-auth-light" {...props}></Icon>
