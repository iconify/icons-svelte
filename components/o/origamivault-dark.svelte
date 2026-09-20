<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iijq8npej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iijq8npej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:origamivault-dark" {...props}></Icon>
