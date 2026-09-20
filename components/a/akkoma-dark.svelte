<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smgz1ib2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="smgz1ib2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:akkoma-dark" {...props}></Icon>
