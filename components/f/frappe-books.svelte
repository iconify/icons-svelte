<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygfchdbyw.css';
import '../../css/m/m8tud7b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ygfchdbyw"/><path class="m8tud7b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-books" {...props}></Icon>
