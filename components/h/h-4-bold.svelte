<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or95d4b4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="or95d4b4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:h-4-bold" {...props}></Icon>
