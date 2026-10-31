<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5nxtr9kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5nxtr9kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bluesky-round" {...props}></Icon>
