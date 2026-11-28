<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcplk2b7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcplk2b7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:globe-solid" {...props}></Icon>
