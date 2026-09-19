<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmtoxfboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmtoxfboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:book-heart" {...props}></Icon>
