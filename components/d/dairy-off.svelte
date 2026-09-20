<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szf_0rulk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szf_0rulk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dairy-off" {...props}></Icon>
