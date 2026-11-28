<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi6h-tbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi6h-tbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layout-masonry-solid" {...props}></Icon>
