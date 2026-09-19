<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3jq2fbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="x3jq2fbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:cente-justify" {...props}></Icon>
