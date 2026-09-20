<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/t/t6p6qua7c.css';
import '../../css/l/l7cqq8bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="t6p6qua7c"/><path class="l7cqq8bfr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:image-saturation" {...props}></Icon>
