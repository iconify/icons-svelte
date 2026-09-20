<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3kxz4x1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3kxz4x1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:crop-landscape" {...props}></Icon>
