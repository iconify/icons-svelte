<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph9zg-b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ph9zg-b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:fullscreen-sharp-fill" {...props}></Icon>
