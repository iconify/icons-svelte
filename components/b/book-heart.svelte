<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up844cc5r.css';
import '../../css/p/p6cb9-b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="up844cc5r"/><path class="p6cb9-b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:book-heart" {...props}></Icon>
