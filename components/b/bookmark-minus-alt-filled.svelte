<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfiyvtbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfiyvtbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bookmark-minus-alt-filled" {...props}></Icon>
