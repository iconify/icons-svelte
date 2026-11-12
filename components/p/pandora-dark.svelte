<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0t9c4vnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s0t9c4vnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pandora-dark" {...props}></Icon>
