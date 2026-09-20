<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gywkzfb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gywkzfb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chevron-right" {...props}></Icon>
