<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm4caib6z.css';
import '../../css/k/k7mhgvbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm4caib6z"/><path class="k7mhgvbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-webcam" {...props}></Icon>
