<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voj5jfbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voj5jfbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:right-top-arrow-circle" {...props}></Icon>
