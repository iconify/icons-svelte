<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojtv12bfi.css';
import '../../css/b/b2qas0b1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ojtv12bfi"/><path class="b2qas0b1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:accumulation-ice" {...props}></Icon>
