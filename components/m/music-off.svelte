<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzpvso9zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzpvso9zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:music-off" {...props}></Icon>
