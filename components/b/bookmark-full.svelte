<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p630u27za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p630u27za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bookmark-full" {...props}></Icon>
