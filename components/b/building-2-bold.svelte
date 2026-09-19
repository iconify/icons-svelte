<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpg89sb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="gpg89sb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:building-2-bold" {...props}></Icon>
