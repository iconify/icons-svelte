<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qziv1ac4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qziv1ac4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:aperture-outline" {...props}></Icon>
