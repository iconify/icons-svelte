<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arlvf1h-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="arlvf1h-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:gift-card-bold" {...props}></Icon>
