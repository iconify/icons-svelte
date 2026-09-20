<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwi-yg3xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwi-yg3xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:book-open" {...props}></Icon>
