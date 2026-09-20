<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqc-2tjjs.css';
import '../../css/i/ix9txabgz.css';
import '../../css/o/opf7hobje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kqc-2tjjs"/><path class="ix9txabgz"/><path class="opf7hobje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:email-envelope-open" {...props}></Icon>
