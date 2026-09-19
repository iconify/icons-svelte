<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akbj3-3cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akbj3-3cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chevron-left" {...props}></Icon>
