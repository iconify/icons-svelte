<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fidptbk8m.css';
import '../../css/v/vb_01fboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fidptbk8m"/><path class="vb_01fboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-waterfall" {...props}></Icon>
