<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_j5ambxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="y_j5ambxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-stand-east-outline" {...props}></Icon>
