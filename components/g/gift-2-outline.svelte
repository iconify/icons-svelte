<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phfy6f6ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="phfy6f6ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:gift-2-outline" {...props}></Icon>
