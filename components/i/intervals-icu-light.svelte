<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shcs-1hry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="shcs-1hry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:intervals-icu-light" {...props}></Icon>
