<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4fj4wl6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p4fj4wl6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:arlo-dark" {...props}></Icon>
