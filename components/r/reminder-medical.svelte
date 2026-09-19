<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0oe49b3b.css';
import '../../css/p/p4r4-2bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a0oe49b3b"/><path class="p4r4-2bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:reminder-medical" {...props}></Icon>
