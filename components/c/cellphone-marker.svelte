<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm7gycb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm7gycb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cellphone-marker" {...props}></Icon>
