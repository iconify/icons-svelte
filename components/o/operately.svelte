<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgxvy9xdu.css';
import '../../css/o/on1z0j2yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zgxvy9xdu"/><path class="on1z0j2yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:operately" {...props}></Icon>
