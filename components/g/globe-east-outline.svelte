<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb9jrro5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rb9jrro5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-east-outline" {...props}></Icon>
