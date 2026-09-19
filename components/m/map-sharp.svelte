<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kretn3bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kretn3bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:map-sharp" {...props}></Icon>
