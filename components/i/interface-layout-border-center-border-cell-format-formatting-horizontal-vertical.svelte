<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mimal_bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mimal_bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-layout-border-center-border-cell-format-formatting-horizontal-vertical" {...props}></Icon>
