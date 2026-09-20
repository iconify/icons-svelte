<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w15e0wb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w15e0wb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:git-merge" {...props}></Icon>
