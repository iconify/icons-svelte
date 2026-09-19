<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edm9wy9_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edm9wy9_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ppt-01" {...props}></Icon>
