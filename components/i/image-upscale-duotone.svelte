<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o5hg3xkds.css';
import '../../css/f/fza34db2x.css';
import '../../css/p/pgn6o9bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o5hg3xkds"/><path class="fza34db2x"/><path class="pgn6o9bgz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:image-upscale-duotone" {...props}></Icon>
