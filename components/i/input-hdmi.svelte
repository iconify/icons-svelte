<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4-nefb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i4-nefb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:input-hdmi" {...props}></Icon>
