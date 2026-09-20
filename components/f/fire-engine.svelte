<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn1h0gzdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn1h0gzdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fire-engine" {...props}></Icon>
