<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm0nid0uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm0nid0uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-peace-variant" {...props}></Icon>
