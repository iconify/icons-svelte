<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh68jtbfr.css';
import '../../css/a/arfms3bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lh68jtbfr"/><path class="arfms3bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:intent-request-active" {...props}></Icon>
