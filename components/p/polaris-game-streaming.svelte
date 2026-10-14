<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz881ov0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dz881ov0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:polaris-game-streaming" {...props}></Icon>
