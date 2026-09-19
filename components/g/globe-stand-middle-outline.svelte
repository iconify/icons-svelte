<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8qo2ibht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="o8qo2ibht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-stand-middle-outline" {...props}></Icon>
