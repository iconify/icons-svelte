<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcac8dzde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcac8dzde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:aiohttp" {...props}></Icon>
