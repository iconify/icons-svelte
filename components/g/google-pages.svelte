<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv2brabrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv2brabrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-pages" {...props}></Icon>
