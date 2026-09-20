<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o44tc3byv.css';
import '../../css/e/eplvi-bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o44tc3byv"/><path class="eplvi-bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermc-velocity-light" {...props}></Icon>
