<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5ko7v8oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="r5ko7v8oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:book-outline" {...props}></Icon>
