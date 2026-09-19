<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d98mzkk1w.css';
import '../../css/t/t9o16wbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d98mzkk1w"/><path class="t9o16wbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:deaf" {...props}></Icon>
