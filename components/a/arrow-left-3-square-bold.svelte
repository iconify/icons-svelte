<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo-k-6ycf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo-k-6ycf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-left-3-square-bold" {...props}></Icon>
