<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x08vz_rzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x08vz_rzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:list-circle-sharp" {...props}></Icon>
