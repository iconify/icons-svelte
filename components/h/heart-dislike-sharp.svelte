<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2yto2b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m2yto2b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:heart-dislike-sharp" {...props}></Icon>
