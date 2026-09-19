<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_z8u2bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1344};
const content = `<path class="c_z8u2bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:fish" {...props}></Icon>
