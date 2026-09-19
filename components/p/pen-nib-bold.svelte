<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5cj3ywlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="p5cj3ywlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pen-nib-bold" {...props}></Icon>
