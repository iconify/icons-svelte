<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqbjj5byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqbjj5byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bookmark-music" {...props}></Icon>
