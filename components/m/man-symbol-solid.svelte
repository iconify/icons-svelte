<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnvm2tb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vnvm2tb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:man-symbol-solid" {...props}></Icon>
