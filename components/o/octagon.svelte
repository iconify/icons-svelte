<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm8gi1btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cm8gi1btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:octagon" {...props}></Icon>
