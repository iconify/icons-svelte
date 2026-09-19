<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqve-bc3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="mqve-bc3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:microphone-slash" {...props}></Icon>
