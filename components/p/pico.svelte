<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l94-5x15h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l94-5x15h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pico" {...props}></Icon>
