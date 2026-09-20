<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma5l8hb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma5l8hb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:creative-commons-nd-line" {...props}></Icon>
