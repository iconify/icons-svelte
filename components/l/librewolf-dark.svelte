<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xon67ijsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xon67ijsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:librewolf-dark" {...props}></Icon>
