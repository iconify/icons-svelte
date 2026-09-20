<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biwqd-khk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="biwqd-khk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:infinity-glyph" {...props}></Icon>
