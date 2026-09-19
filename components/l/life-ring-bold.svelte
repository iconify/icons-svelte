<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm2av2mxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zm2av2mxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:life-ring-bold" {...props}></Icon>
