<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcjif3b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcjif3b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:indent-round" {...props}></Icon>
