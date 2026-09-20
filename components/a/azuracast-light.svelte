<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pefbi7b3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pefbi7b3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:azuracast-light" {...props}></Icon>
