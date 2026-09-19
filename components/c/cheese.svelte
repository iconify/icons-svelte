<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxa0j-bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mxa0j-bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cheese" {...props}></Icon>
