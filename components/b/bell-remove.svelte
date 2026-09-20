<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caz0ggb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caz0ggb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell-remove" {...props}></Icon>
