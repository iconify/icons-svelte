<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftv6d47py.css';
import '../../css/a/ananko81k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ftv6d47py"/><path class="ananko81k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:connect-reference" {...props}></Icon>
