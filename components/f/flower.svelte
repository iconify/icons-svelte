<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/o/oaprlkznb.css';
import '../../css/w/w5qlhtw1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="oaprlkznb"/><path class="w5qlhtw1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flower" {...props}></Icon>
