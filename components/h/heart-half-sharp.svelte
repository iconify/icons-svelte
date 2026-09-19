<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dshn71jrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dshn71jrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:heart-half-sharp" {...props}></Icon>
