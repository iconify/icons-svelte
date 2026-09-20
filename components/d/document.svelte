<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdvd8x__s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdvd8x__s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:document" {...props}></Icon>
