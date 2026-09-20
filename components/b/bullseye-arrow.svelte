<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi434z6ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi434z6ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:bullseye-arrow" {...props}></Icon>
