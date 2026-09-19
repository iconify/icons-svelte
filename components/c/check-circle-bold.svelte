<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alw736d5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="alw736d5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:check-circle-bold" {...props}></Icon>
