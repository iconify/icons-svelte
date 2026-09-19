<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhvt2-bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xhvt2-bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-earth-outline" {...props}></Icon>
