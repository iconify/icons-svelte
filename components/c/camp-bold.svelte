<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl7j8ub1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hl7j8ub1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:camp-bold" {...props}></Icon>
