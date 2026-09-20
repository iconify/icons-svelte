<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duygepb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="duygepb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:missing-symbol" {...props}></Icon>
