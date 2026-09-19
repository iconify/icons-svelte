<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt0s0kb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="jt0s0kb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:layer-group-outline" {...props}></Icon>
