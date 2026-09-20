<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdglqd46z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rdglqd46z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:acorn" {...props}></Icon>
