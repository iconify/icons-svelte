<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvr2kcchl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wvr2kcchl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:file" {...props}></Icon>
