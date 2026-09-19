<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udfcfobvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udfcfobvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:playlist-shuffle-duotone" {...props}></Icon>
