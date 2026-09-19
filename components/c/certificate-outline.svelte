<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahwwyhbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ahwwyhbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:certificate-outline" {...props}></Icon>
