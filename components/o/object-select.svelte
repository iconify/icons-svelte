<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki54wzl-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ki54wzl-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:object-select" {...props}></Icon>
