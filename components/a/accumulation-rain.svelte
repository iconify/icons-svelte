<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goxbou09t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="goxbou09t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:accumulation-rain" {...props}></Icon>
