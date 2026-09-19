<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u98ht8bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="u98ht8bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:dizzy-bold" {...props}></Icon>
