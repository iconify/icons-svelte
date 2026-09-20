<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu-jtebze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tu-jtebze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hermesseg-light" {...props}></Icon>
