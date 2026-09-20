<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du-cu2mmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="du-cu2mmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:man-symbol-flat" {...props}></Icon>
