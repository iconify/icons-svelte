<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pytnb7b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pytnb7b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:location-plus" {...props}></Icon>
