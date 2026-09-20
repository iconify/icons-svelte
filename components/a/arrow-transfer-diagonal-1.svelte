<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh1gwvm1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mh1gwvm1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-transfer-diagonal-1" {...props}></Icon>
