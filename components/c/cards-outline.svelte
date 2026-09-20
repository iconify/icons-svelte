<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2nv7g9ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2nv7g9ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cards-outline" {...props}></Icon>
