<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddo390ave.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddo390ave"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bed-king" {...props}></Icon>
