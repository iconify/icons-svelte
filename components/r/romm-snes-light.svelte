<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yes_z39me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yes_z39me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:romm-snes-light" {...props}></Icon>
