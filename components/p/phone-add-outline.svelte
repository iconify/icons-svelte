<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7ap2g0om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c7ap2g0om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:phone-add-outline" {...props}></Icon>
