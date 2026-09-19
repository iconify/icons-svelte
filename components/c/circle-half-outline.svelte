<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrokb7bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zrokb7bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:circle-half-outline" {...props}></Icon>
