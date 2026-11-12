<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj5k-rjmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hj5k-rjmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calibre-web" {...props}></Icon>
