<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpgyb1h7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kpgyb1h7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-expand-diagonal-1-expand-resize-bigger-diagonal-smaller-size-arrow-arrows-big" {...props}></Icon>
