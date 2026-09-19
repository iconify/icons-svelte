<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/occxhccgf.css';
import '../../css/m/mxusxgb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="occxhccgf"/><path class="mxusxgb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:policy" {...props}></Icon>
