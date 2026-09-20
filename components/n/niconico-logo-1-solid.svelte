<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sncsgpbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sncsgpbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:niconico-logo-1-solid" {...props}></Icon>
