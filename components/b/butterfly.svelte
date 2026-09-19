<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5r7ey5cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5r7ey5cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:butterfly" {...props}></Icon>
