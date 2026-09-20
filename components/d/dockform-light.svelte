<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy0b4ab-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xy0b4ab-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockform-light" {...props}></Icon>
