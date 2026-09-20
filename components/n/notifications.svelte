<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt-w9bcpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dt-w9bcpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:notifications" {...props}></Icon>
