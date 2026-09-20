<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0gjirnau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h0gjirnau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:authelia-light" {...props}></Icon>
