<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygk6s-8dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygk6s-8dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:brackets-off" {...props}></Icon>
