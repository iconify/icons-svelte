<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-4g-9byg.css';
import '../../css/a/a2og3c3yl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-4g-9byg"/><path class="a2og3c3yl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-star" {...props}></Icon>
