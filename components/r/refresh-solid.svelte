<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brxx-opev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brxx-opev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:refresh-solid" {...props}></Icon>
