<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyp-bobqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="lyp-bobqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:q-square" {...props}></Icon>
