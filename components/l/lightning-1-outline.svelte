<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e58o2jowk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="e58o2jowk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:lightning-1-outline" {...props}></Icon>
