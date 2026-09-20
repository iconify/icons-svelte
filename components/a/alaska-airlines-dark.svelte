<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1w4zbk0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i1w4zbk0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alaska-airlines-dark" {...props}></Icon>
