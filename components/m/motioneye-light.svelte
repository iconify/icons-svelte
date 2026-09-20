<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivimh0l5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ivimh0l5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:motioneye-light" {...props}></Icon>
