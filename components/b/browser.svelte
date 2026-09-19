<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yel91y_cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yel91y_cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:browser" {...props}></Icon>
