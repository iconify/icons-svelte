<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqxiurbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="iqxiurbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hourglass-0-bold" {...props}></Icon>
