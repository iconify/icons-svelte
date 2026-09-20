<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyss1-bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyss1-bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:location-fill" {...props}></Icon>
