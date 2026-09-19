<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxoghot-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zxoghot-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:mouse-2-outline" {...props}></Icon>
