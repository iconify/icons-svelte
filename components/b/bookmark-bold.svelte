<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv3wqwbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv3wqwbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:bookmark-bold" {...props}></Icon>
