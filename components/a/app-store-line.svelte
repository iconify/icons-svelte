<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkn9-fbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkn9-fbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:app-store-line" {...props}></Icon>
