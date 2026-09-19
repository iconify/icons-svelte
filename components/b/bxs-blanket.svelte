<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy0e5mmid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy0e5mmid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-blanket" {...props}></Icon>
