<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzdi1-b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="rzdi1-b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bottle-droplet" {...props}></Icon>
