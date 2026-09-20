<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxjyqn1xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dxjyqn1xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:client-interface" {...props}></Icon>
