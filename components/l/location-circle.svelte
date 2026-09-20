<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x84wkm2wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x84wkm2wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:location-circle" {...props}></Icon>
