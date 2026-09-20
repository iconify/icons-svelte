<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4x21rbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x4x21rbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-rewind-2-solid" {...props}></Icon>
