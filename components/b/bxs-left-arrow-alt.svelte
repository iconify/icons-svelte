<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z512x4bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z512x4bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-left-arrow-alt" {...props}></Icon>
