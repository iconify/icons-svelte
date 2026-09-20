<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/way8m64gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="way8m64gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nodecast-tv-dark" {...props}></Icon>
