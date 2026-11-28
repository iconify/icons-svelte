<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llxojwb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llxojwb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hotel-heart" {...props}></Icon>
