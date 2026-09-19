<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4mzg_bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x4mzg_bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:media-skip-backward" {...props}></Icon>
