<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx5jtdgol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="sx5jtdgol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-thick-up" {...props}></Icon>
