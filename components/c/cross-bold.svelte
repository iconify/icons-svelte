<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyn8p9byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tyn8p9byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cross-bold" {...props}></Icon>
