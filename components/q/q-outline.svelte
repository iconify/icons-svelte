<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcta_v5_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dcta_v5_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:q-outline" {...props}></Icon>
