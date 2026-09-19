<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8ei37bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8ei37bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:right-angle-triangle-half-filled" {...props}></Icon>
