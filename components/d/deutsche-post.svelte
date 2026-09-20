<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uub0g_gkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uub0g_gkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deutsche-post" {...props}></Icon>
