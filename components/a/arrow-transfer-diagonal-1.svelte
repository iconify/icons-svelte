<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-7-34bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="b-7-34bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-transfer-diagonal-1" {...props}></Icon>
