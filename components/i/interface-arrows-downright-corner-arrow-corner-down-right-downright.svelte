<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0ce-xmes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="x0ce-xmes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-downright-corner-arrow-corner-down-right-downright" {...props}></Icon>
