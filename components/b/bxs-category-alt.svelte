<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8kn2tjuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8kn2tjuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-category-alt" {...props}></Icon>
