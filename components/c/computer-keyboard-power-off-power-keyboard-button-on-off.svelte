<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/y/yph-txb3i.css';
import '../../css/f/f-2zhcd9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><rect class="yph-txb3i"/><path class="f-2zhcd9i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-keyboard-power-off-power-keyboard-button-on-off" {...props}></Icon>
