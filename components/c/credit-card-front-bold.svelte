<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiu0-hwpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="uiu0-hwpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:credit-card-front-bold" {...props}></Icon>
