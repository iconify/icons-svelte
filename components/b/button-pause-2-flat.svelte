<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5x8obe1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x5x8obe1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:button-pause-2-flat" {...props}></Icon>
