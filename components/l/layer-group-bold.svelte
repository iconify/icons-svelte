<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xap50hwvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xap50hwvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:layer-group-bold" {...props}></Icon>
