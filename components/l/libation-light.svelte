<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgzc-tbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zgzc-tbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:libation-light" {...props}></Icon>
