<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln_y4ob5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln_y4ob5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jellyseerr" {...props}></Icon>
