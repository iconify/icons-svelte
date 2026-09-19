<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phb2crpck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="phb2crpck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:night-outline" {...props}></Icon>
