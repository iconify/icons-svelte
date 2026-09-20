<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heg2zcb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="heg2zcb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-horizontal-expand-resize-bigger-horizontal-small-smaller-size-arrow-arrows-big" {...props}></Icon>
