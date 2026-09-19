<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqmy5ybif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqmy5ybif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:berlin" {...props}></Icon>
