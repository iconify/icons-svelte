<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry1vzxbgx.css';
import '../../css/h/hllb8zubv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry1vzxbgx"/><path class="hllb8zubv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:filter-close-bold" {...props}></Icon>
