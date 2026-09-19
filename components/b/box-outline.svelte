<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2_h6rb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="o2_h6rb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:box-outline" {...props}></Icon>
