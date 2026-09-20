<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lux-p9t9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lux-p9t9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:giraffile" {...props}></Icon>
