<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbeushb0e.css';
import '../../css/r/rik56bhzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qbeushb0e"/><path class="rik56bhzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:food-drink-desert-cupcake" {...props}></Icon>
