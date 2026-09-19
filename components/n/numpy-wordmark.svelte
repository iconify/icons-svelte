<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t09dwgwot.css';
import '../../css/z/zc4v9w_9s.css';
import '../../css/p/p57ho085m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="t09dwgwot"/><path class="zc4v9w_9s"/><path class="p57ho085m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:numpy-wordmark" {...props}></Icon>
