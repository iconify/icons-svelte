<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2ra-1bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2ra-1bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-u-right-bottom-bold" {...props}></Icon>
