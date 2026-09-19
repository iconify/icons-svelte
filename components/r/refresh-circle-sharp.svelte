<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhug2eb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vhug2eb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:refresh-circle-sharp" {...props}></Icon>
