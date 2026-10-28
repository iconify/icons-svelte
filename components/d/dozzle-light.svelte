<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtw5n0crk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vtw5n0crk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dozzle-light" {...props}></Icon>
