<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg4qlh80c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rg4qlh80c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-k-box-outline" {...props}></Icon>
