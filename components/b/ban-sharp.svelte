<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn-vlsb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xn-vlsb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:ban-sharp" {...props}></Icon>
