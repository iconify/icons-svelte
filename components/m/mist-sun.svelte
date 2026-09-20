<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cauac2ggz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cauac2ggz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:mist-sun" {...props}></Icon>
