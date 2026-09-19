<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhcm4hbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nhcm4hbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-outline" {...props}></Icon>
