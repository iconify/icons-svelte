<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w33oqo5oh.css';
import '../../css/c/cjcvn3b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="w33oqo5oh"/><path class="cjcvn3b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:rancher-wordmark" {...props}></Icon>
