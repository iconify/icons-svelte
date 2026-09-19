<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrtsf18ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrtsf18ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bookmark-heart" {...props}></Icon>
