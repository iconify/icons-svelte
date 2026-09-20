<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp4pf7ssu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp4pf7ssu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bookmark-2-fill" {...props}></Icon>
