<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np3zoh3zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np3zoh3zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:chrome-web-store" {...props}></Icon>
