<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdu4dczmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mdu4dczmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:power-norway-light" {...props}></Icon>
