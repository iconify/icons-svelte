<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftv6d47py.css';
import '../../css/l/lz96xw1en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ftv6d47py"/><path class="lz96xw1en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:gem-reference" {...props}></Icon>
