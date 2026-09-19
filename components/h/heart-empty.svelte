<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzna4a00y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1063,"height":1000};
const content = `<path class="lzna4a00y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:heart-empty" {...props}></Icon>
