<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw90ydbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bw90ydbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:p-wide-on-parking-line" {...props}></Icon>
