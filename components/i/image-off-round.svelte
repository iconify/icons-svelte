<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm2s2x7kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm2s2x7kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:image-off-round" {...props}></Icon>
