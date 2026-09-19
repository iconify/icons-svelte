<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9uvcsbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="n9uvcsbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:mobile-bold" {...props}></Icon>
