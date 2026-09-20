<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/totc_uaeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="totc_uaeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:money-usd" {...props}></Icon>
