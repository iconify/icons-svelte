<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msid8bbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msid8bbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bookmark-multiple-outline" {...props}></Icon>
