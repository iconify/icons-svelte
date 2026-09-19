<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt8gsz3uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tt8gsz3uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pen-bold" {...props}></Icon>
