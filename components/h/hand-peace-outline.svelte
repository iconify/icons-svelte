<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a91hmccve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a91hmccve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-peace-outline" {...props}></Icon>
