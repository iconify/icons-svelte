<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj079gbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj079gbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:money-sharp" {...props}></Icon>
