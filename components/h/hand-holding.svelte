<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohrg4zbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ohrg4zbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:hand-holding" {...props}></Icon>
