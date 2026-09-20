<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/naw5s4b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="naw5s4b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-light" {...props}></Icon>
