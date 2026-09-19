<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjmbb-4xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tjmbb-4xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-americas-outline" {...props}></Icon>
