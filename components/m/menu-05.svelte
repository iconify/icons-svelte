<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcg4t3b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcg4t3b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:menu-05" {...props}></Icon>
