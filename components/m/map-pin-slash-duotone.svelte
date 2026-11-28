<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sg5g8obyv.css';
import '../../css/s/sgwj7m_pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="sg5g8obyv"/><path class="sgwj7m_pu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:map-pin-slash-duotone" {...props}></Icon>
