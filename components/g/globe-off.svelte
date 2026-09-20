<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy6gawa6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy6gawa6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:globe-off" {...props}></Icon>
