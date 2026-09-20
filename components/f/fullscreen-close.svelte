<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn7wlqbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vn7wlqbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:fullscreen-close" {...props}></Icon>
