<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_3xj1bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_3xj1bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart-crack-gloss" {...props}></Icon>
