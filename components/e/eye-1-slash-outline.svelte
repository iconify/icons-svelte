<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-cmjqifn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="h-cmjqifn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:eye-1-slash-outline" {...props}></Icon>
