<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj64-jb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vj64-jb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homedock-os-dark" {...props}></Icon>
