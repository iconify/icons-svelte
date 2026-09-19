<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8n_19bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t8n_19bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:location-sharp" {...props}></Icon>
