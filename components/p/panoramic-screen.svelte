<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su4aumbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su4aumbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:panoramic-screen" {...props}></Icon>
