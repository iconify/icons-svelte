<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j34d9k6ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j34d9k6ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bookmark-heart-filled" {...props}></Icon>
