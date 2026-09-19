<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7qq7q29t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="i7qq7q29t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bells-outline" {...props}></Icon>
