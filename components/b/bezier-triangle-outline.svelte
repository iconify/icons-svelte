<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvc3xoy3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nvc3xoy3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bezier-triangle-outline" {...props}></Icon>
