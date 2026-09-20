<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1e-couig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1e-couig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bookmarks-fill" {...props}></Icon>
