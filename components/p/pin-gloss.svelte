<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsp7bnb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsp7bnb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pin-gloss" {...props}></Icon>
