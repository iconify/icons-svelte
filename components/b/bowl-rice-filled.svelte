<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn__3i8jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn__3i8jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bowl-rice-filled" {...props}></Icon>
