<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orre3bifv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="orre3bifv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:peace-symbol-flat" {...props}></Icon>
