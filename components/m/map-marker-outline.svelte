<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6ya0ub4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l6ya0ub4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:map-marker-outline" {...props}></Icon>
