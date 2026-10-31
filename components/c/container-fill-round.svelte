<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haj0-xbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haj0-xbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:container-fill-round" {...props}></Icon>
